<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v_fkiebln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v_fkiebln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:sky" /></template>
