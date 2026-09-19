<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cfkx1ubzo.css';
import '../../css/w/wq8x2ubgv.css';
import '../../css/w/wge49ob4x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="cfkx1ubzo"/><circle class="wq8x2ubgv"/><path class="wge49ob4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:speaker-fill" /></template>
