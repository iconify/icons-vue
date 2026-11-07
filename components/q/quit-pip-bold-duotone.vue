<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdob9slbu.css';
import '../../css/w/womkpu5er.css';
import '../../css/d/dhs0g5bcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdob9slbu"/><path class="womkpu5er"/><path class="dhs0g5bcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quit-pip-bold-duotone" /></template>
