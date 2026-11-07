<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hzylw2bqw.css';
import '../../css/k/kxpdd-d5x.css';
import '../../css/t/tcxp3ubtd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hzylw2bqw"/><path class="kxpdd-d5x"/><path class="tcxp3ubtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-bold-duotone" /></template>
