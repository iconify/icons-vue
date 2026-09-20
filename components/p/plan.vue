<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddlerbc9s.css';
import '../../css/w/w158vz8lp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddlerbc9s"/><path class="w158vz8lp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:plan" /></template>
