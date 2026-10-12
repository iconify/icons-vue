<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hpnd9lbjp.css';
import '../../css/g/gqykg4buz.css';
import '../../css/w/w6vmw__do.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hpnd9lbjp"/><path class="gqykg4buz"/><path class="w6vmw__do"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:telescope-duotone" /></template>
