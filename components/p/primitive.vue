<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dn-6xjbzp.css';
import '../../css/t/tk3rezb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="dn-6xjbzp"/><path class="tk3rezb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:primitive" /></template>
