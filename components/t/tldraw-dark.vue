<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7i7nxq4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="b7i7nxq4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tldraw-dark" /></template>
