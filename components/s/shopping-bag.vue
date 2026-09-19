<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho_irrb9b.css';
import '../../css/v/vzi465tms.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="duoicon-secondary-layer ho_irrb9b"/><path class="duoicon-primary-layer vzi465tms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="duo-icons:shopping-bag" /></template>
