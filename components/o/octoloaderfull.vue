<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goo-ghg2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="goo-ghg2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:octoloaderfull" /></template>
