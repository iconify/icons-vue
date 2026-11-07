<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jol1kjm1u.css';
import '../../css/f/fxwq1cqvv.css';
import '../../css/t/tcadmdbou.css';
import '../../css/t/ts72lmbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jol1kjm1u"/><path class="fxwq1cqvv"/><path class="tcadmdbou"/><path class="ts72lmbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-money-bold-duotone" /></template>
