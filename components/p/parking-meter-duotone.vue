<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/v/v0-xpbb2b.css';
import '../../css/d/d6xrfdbqy.css';
import '../../css/k/kh3h7ac0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="v0-xpbb2b"/><path class="d6xrfdbqy"/><path class="kh3h7ac0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:parking-meter-duotone" /></template>
