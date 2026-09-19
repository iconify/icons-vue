<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guw_mk73j.css';
import '../../css/i/ilmsi6bmd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="guw_mk73j"/><path clip-rule="evenodd" class="ilmsi6bmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:question-filled" /></template>
