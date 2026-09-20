<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob62dr7jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob62dr7jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:spacemacs" /></template>
