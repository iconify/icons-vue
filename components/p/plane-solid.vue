<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x05awwcjo.css';
import '../../css/e/eux30obfs.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 x05awwcjo"/><path class="clr-i-solid clr-i-solid-path-2 eux30obfs"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:plane-solid" /></template>
