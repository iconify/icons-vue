<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9kkcbbd.css';
import '../../css/d/d56vnzbxk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq9kkcbbd"/><path class="d56vnzbxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pen-bold-duotone" /></template>
