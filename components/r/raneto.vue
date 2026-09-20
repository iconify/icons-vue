<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vaapy-bnd.css';
import '../../css/z/zl8qabcpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vaapy-bnd"/><path class="zl8qabcpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:raneto" /></template>
