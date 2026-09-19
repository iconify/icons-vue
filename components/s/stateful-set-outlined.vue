<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azvt5ojhn.css';
import '../../css/s/s69j4pb6w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="azvt5ojhn"/><path class="s69j4pb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:stateful-set-outlined" /></template>
