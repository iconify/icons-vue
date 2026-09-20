<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkil4xoxe.css';
import '../../css/k/kao9e10zu.css';
import '../../css/v/v_u95_e3w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkil4xoxe"/><path class="kao9e10zu"/><path class="v_u95_e3w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:wallet-duotone" /></template>
