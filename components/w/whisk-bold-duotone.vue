<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bji9ibcha.css';
import '../../css/b/boq_u9ond.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bji9ibcha"/><path class="boq_u9ond"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whisk-bold-duotone" /></template>
