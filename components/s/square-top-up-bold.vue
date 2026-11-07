<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tw3onyotj.css';
import '../../css/z/zfllz3bry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tw3onyotj"/><path class="zfllz3bry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-top-up-bold" /></template>
