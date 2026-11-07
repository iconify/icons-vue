<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r5qmym-cz.css';
import '../../css/i/iln029b4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r5qmym-cz"/><path clip-rule="evenodd" class="iln029b4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panorama-bold" /></template>
