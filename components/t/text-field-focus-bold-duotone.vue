<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqt3vmb-u.css';
import '../../css/j/jjt0fksdh.css';
import '../../css/s/spi5mob-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqt3vmb-u"/><path class="jjt0fksdh"/><path class="spi5mob-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-field-focus-bold-duotone" /></template>
