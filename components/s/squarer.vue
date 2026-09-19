<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/el_9stbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="el_9stbak"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:squarer" /></template>
