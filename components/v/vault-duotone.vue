<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3x5_inum.css';
import '../../css/w/wx5lbcbct.css';
import '../../css/a/afas8h87o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3x5_inum"/><path class="wx5lbcbct"/><path class="afas8h87o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:vault-duotone" /></template>
