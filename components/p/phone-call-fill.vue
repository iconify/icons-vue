<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np3fkg3rl.css';
import '../../css/t/tht3gpbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np3fkg3rl"/><path class="tht3gpbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:phone-call-fill" /></template>
