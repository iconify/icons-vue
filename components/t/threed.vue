<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfgx_pj9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":960,"height":1024};
const content = `<path class="hfgx_pj9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:threed" /></template>
