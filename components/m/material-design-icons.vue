<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhd69yzkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhd69yzkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:material-design-icons" /></template>
