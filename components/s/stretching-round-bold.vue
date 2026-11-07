<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ay5dbdcag.css';
import '../../css/t/twhnk8blw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay5dbdcag"/><path clip-rule="evenodd" class="twhnk8blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:stretching-round-bold" /></template>
