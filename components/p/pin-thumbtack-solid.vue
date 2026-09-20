<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qe25r3bdn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qe25r3bdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:pin-thumbtack-solid" /></template>
