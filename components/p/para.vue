<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t--a6rbsb.css';
import '../../css/r/r1oc-kbvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t--a6rbsb"/><path class="r1oc-kbvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:para" /></template>
