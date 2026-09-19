<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spfjnobdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spfjnobdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:three-d" /></template>
