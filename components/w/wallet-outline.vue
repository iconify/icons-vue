<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g95e799uz.css';
import '../../css/v/vpo1j0hds.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g95e799uz"/><path clip-rule="evenodd" class="vpo1j0hds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:wallet-outline" /></template>
