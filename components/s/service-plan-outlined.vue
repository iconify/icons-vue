<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sxydanhms.css';
import '../../css/e/egw0_e_yk.css';
import '../../css/g/grhwfqo-l.css';
import '../../css/d/dtbe3abpb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxydanhms"/><circle class="egw0_e_yk"/><path class="grhwfqo-l"/><path class="dtbe3abpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:service-plan-outlined" /></template>
