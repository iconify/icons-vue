<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9nmr3btp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="v9nmr3btp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:startup-remix" /></template>
