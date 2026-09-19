<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcckeccvu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wcckeccvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:mini-camera" /></template>
