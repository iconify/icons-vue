<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tx20rqbza.css';
import '../../css/m/m94p08b9v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx20rqbza"/><path clip-rule="evenodd" class="m94p08b9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:user-clock-solid" /></template>
