<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/btp9mjb_l.css';
import '../../css/h/ho371t52a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="btp9mjb_l"/><path class="ho371t52a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-bottom-up-bold" /></template>
