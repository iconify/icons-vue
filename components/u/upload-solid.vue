<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ac1_qub2u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ac1_qub2u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:upload-solid" /></template>
