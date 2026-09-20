<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dmx-_ob5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dmx-_ob5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:slack-alt" /></template>
