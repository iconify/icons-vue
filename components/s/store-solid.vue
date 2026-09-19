<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bppa0jbgn.css';
import '../../css/o/o2-cvm_8e.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="bppa0jbgn clr-i-solid clr-i-solid-path-1"/><path class="clr-i-solid clr-i-solid-path-2 o2-cvm_8e"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:store-solid" /></template>
