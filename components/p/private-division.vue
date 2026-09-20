<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2e82lb7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2e82lb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:private-division" /></template>
