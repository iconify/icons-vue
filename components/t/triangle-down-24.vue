<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hlhawqkmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hlhawqkmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:triangle-down-24" /></template>
