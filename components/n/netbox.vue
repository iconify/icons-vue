<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmu1e4ohr.css';
import '../../css/d/drunhgb2r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zmu1e4ohr"/><path class="drunhgb2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:netbox" /></template>
