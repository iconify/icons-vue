<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fvrtv7bqi.css';
import '../../css/p/pazdl73hk.css';
import '../../css/p/p7nvdbbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fvrtv7bqi"/><path class="pazdl73hk"/><path class="p7nvdbbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:refuse-truck-20-bold" /></template>
