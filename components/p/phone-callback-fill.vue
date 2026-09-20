<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ypft5mbdm.css';
import '../../css/j/jdgd8ngaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ypft5mbdm"/><path class="jdgd8ngaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:phone-callback-fill" /></template>
