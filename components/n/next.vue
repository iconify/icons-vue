<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt2o0cv8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kt2o0cv8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:next" /></template>
