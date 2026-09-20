<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slqn7pbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="slqn7pbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:megaphone-solid" /></template>
