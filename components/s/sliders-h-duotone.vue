<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sk1ji3fyx.css';
import '../../css/v/v4puv_b2i.css';
import '../../css/i/iwp2c6aew.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sk1ji3fyx"/><path class="v4puv_b2i"/><path clip-rule="evenodd" class="iwp2c6aew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sliders-h-duotone" /></template>
