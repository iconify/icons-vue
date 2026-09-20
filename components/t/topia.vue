<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi8b-cbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vi8b-cbju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:topia" /></template>
