<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/et59vtbnu.css';
import '../../css/t/tmd21lv3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="et59vtbnu"/><path class="tmd21lv3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-bold-duotone" /></template>
