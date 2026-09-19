<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sn9ruabtp.css';
import '../../css/c/cws_xd9jl.css';
import '../../css/j/jluxn4buv.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 sn9ruabtp"/><path class="clr-i-outline clr-i-outline-path-2 cws_xd9jl"/><path class="clr-i-outline clr-i-outline-path-3 jluxn4buv"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:pinned-line" /></template>
