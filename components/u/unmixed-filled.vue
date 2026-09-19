<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jsm0l9bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jsm0l9bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:unmixed-filled" /></template>
