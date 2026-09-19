<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gen1u6ueu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gen1u6ueu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:roborock-logo" /></template>
