<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vh7ouzyov.css';
import '../../css/l/l14k1ybbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh7ouzyov"/><path clip-rule="evenodd" class="l14k1ybbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:yarn" /></template>
