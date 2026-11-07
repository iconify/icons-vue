<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixjkhbszw.css';
import '../../css/l/lvp3cpbur.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixjkhbszw"/><path class="lvp3cpbur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:text-underline-bold-duotone" /></template>
