<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q798o54jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q798o54jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:weather-cloudy" /></template>
