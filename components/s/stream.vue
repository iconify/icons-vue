<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo9rfd2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mo9rfd2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:stream" /></template>
