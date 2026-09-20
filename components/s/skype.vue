<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mkprlx1pi.css';
import '../../css/i/id8zlgdpt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkprlx1pi"/><path class="id8zlgdpt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:skype" /></template>
