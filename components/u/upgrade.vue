<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecm__i54a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ecm__i54a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:upgrade" /></template>
