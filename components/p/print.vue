<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9varz0ss.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v9varz0ss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:print" /></template>
