<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eq7odubmz.css';
import '../../css/o/ot9dk8dyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="eq7odubmz"/><path class="ot9dk8dyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:voicemail-20" /></template>
