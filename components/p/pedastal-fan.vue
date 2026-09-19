<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdhts7ruk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdhts7ruk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:pedastal-fan" /></template>
