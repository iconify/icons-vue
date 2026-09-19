<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3ny5kbwg.css';
import '../../css/d/dwgdao0sa.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c3ny5kbwg clr-i-outline clr-i-outline-path-1"/><circle class="clr-i-outline clr-i-outline-path-2 dwgdao0sa"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:wallet-line" /></template>
