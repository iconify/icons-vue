<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mql5pkbnr.css';
import '../../css/p/p68cdpbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mql5pkbnr"/><path class="p68cdpbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:tennis-match-alt" /></template>
