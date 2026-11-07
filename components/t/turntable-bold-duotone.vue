<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vxz8lnubg.css';
import '../../css/e/eo0cog95z.css';
import '../../css/w/w8t6fkc8x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vxz8lnubg"/><path clip-rule="evenodd" class="eo0cog95z"/><path clip-rule="evenodd" class="w8t6fkc8x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:turntable-bold-duotone" /></template>
