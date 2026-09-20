<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m21o_tg9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m21o_tg9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:preact" /></template>
