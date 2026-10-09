<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gob-ytbgf.css';
import '../../css/n/nb2fp75rv.css';
import '../../css/u/ubixxqbpx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gob-ytbgf"/><path class="nb2fp75rv"/><path class="ubixxqbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:small-wind-turbine-20" /></template>
