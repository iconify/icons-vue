<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymn00fgdm.css';
import '../../css/v/vowsucibp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="ymn00fgdm"/><path class="vowsucibp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:user-add" /></template>
