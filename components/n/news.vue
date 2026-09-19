<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s4v6-8p-u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="s4v6-8p-u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:news" /></template>
