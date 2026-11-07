<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f0nhpsynn.css';
import '../../css/r/rarrkzbto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="f0nhpsynn"/><ellipse class="rarrkzbto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:user-rounded-bold-duotone" /></template>
