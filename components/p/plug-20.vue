<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dl3kfub2g.css';
import '../../css/q/quvshjb7w.css';
import '../../css/g/g4ik5wbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dl3kfub2g"/><path class="quvshjb7w"/><path class="g4ik5wbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plug-20" /></template>
