<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wu-cc3sah.css';
import '../../css/o/oei2zdbxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu-cc3sah"/><path class="oei2zdbxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:round-arrow-left-up-bold-duotone" /></template>
