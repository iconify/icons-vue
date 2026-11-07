<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c39303b3x.css';
import '../../css/g/gdbv4de5j.css';
import '../../css/t/tcxp3ubtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c39303b3x"/><path class="gdbv4de5j"/><path class="tcxp3ubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-2-bold-duotone" /></template>
