<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwqcolm5j.css';
import '../../css/h/hp5qtbbru.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 wwqcolm5j"/><path class="clr-i-solid clr-i-solid-path-2 hp5qtbbru"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:microphone-solid" /></template>
