<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-id4q7lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-id4q7lk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:transaction" /></template>
