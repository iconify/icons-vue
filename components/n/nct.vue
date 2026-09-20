<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghx9yzbxt.css';
import '../../css/k/ktjyq3bmf.css';
import '../../css/v/v0b7vsbjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghx9yzbxt"/><path class="ktjyq3bmf"/><path class="v0b7vsbjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:nct" /></template>
