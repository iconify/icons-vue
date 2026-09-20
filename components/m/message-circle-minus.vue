<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_xn3hb7i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_xn3hb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-circle-minus" /></template>
