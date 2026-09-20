<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q2nio-cvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2nio-cvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:panel-right-open-fill" /></template>
