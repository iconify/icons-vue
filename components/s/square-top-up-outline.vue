<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rszymacgm.css';
import '../../css/m/m31n_gbkv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rszymacgm"/><path class="m31n_gbkv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-top-up-outline" /></template>
