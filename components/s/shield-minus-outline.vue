<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ty867ghkp.css';
import '../../css/q/qwjuf14gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ty867ghkp"/><path clip-rule="evenodd" class="qwjuf14gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shield-minus-outline" /></template>
