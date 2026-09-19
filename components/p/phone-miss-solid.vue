<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4fpjkz2f.css';
import '../../css/j/jq6ai4chg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b4fpjkz2f"/><path class="jq6ai4chg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:phone-miss-solid" /></template>
