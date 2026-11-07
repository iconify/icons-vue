<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7ll2egzf.css';
import '../../css/v/v2ruv0bjc.css';
import '../../css/m/mbh0r8bba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ll2egzf"/><path class="v2ruv0bjc"/><path clip-rule="evenodd" class="mbh0r8bba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:station-minimalistic-bold" /></template>
