<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6jgc5b_g.css';
import '../../css/h/hllvxmbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f6jgc5b_g"/><path class="hllvxmbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:settings-thick-duotone" /></template>
