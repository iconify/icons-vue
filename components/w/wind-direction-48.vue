<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0rf3fb-u.css';
import '../../css/s/s_gjiybtk.css';
import '../../css/v/v3cog_bvy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o0rf3fb-u"/><path class="s_gjiybtk"/><path class="v3cog_bvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:wind-direction-48" /></template>
