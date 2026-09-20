<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig8ne5sll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ig8ne5sll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:pandora-light" /></template>
