<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de4w5bjhn.css';
import '../../css/h/h6vym3bzz.css';
import '../../css/s/s_j32c9mx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="de4w5bjhn"/><path clip-rule="evenodd" class="h6vym3bzz"/><path clip-rule="evenodd" class="s_j32c9mx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:phone-calling-rounded-outline" /></template>
