<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bl88kwb7m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bl88kwb7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:php" /></template>
