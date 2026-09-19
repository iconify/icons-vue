<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mihn-ac0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mihn-ac0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:triangle-filled" /></template>
