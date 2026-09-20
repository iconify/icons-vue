<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fitiderwm.css';
import '../../css/g/g8_by6k8l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fitiderwm"/><path class="g8_by6k8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sensitive-duotone" /></template>
