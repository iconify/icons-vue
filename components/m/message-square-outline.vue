<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7gfsbb7m.css';
import '../../css/f/f-ksdqydc.css';
import '../../css/s/spxynnb0e.css';
import '../../css/p/p20qyyjsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="c7gfsbb7m"/><circle class="f-ksdqydc"/><circle class="spxynnb0e"/><path class="p20qyyjsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:message-square-outline" /></template>
