<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnh4tjnml.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="qnh4tjnml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:usershield" /></template>
