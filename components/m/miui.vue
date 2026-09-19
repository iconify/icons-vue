<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wp_i_kw1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":640};
const content = `<path class="wp_i_kw1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:miui" /></template>
