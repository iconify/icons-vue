<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bppa0jbgn.css';
import '../../css/z/znxmuy0xb.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bppa0jbgn clr-i-outline clr-i-outline-path-1"/><path class="clr-i-outline clr-i-outline-path-2 znxmuy0xb"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:store-line" /></template>
