<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v31scrb0w.css';
import '../../css/s/sgn1aep-s.css';
import '../../css/u/ufg40xb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v31scrb0w"/><path class="sgn1aep-s"/><path class="ufg40xb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:spedometer-low-bold-duotone" /></template>
