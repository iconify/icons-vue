<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gc8ekcbco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gc8ekcbco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:tolgee-dark" /></template>
