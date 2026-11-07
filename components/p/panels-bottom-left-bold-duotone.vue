<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k408t5b_f.css';
import '../../css/u/u7zit7oth.css';
import '../../css/i/iz-4hbcxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k408t5b_f"/><path class="u7zit7oth"/><path class="iz-4hbcxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:panels-bottom-left-bold-duotone" /></template>
