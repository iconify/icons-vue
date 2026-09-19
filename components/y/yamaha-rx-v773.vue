<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1728rb5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1728rb5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:yamaha-rx-v773" /></template>
