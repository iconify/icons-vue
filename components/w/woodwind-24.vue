<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt5jg9bzv.css';
import '../../css/e/ecruigbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kt5jg9bzv"/><path class="ecruigbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:woodwind-24" /></template>
