<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2q_mob-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v2q_mob-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-up" /></template>
