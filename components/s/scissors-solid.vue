<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfqkh-b5y.css';
import '../../css/h/ho3fq4w0k.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 vfqkh-b5y"/><path class="clr-i-solid clr-i-solid-path-2 ho3fq4w0k"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:scissors-solid" /></template>
