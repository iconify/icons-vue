<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wsh4t_buo.css';
import '../../css/u/ug5d9ob-u.css';
import '../../css/h/hok4tgbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wsh4t_buo"/><path class="ug5d9ob-u"/><path class="hok4tgbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:send-to-back-duotone" /></template>
