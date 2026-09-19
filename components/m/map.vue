<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w_vpm5byk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_vpm5byk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:map" /></template>
