<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_93pgbru.css';
import '../../css/r/ra-4wynoj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_93pgbru"/><path class="ra-4wynoj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:sign-out-alt-fill" /></template>
