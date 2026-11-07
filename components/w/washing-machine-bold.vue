<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kod2frlkh.css';
import '../../css/k/k_dz1obwi.css';
import '../../css/t/tr03jc-wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kod2frlkh"/><path class="k_dz1obwi"/><path clip-rule="evenodd" class="tr03jc-wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:washing-machine-bold" /></template>
