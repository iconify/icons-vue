<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1bdn5bgd.css';
import '../../css/u/ufxyupbnl.css';
import '../../css/q/qmep5shkh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="r1bdn5bgd"/><rect class="ufxyupbnl"/><rect class="qmep5shkh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:menu-filled" /></template>
