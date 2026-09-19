<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iio3flbyw.css';
import '../../css/u/u3637ccul.css';
import '../../css/r/rc8bmi5tc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iio3flbyw"/><circle class="u3637ccul"/><path class="rc8bmi5tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:warning" /></template>
