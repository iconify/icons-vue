<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ls6i98u3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="ls6i98u3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:phone-notification-solid" /></template>
