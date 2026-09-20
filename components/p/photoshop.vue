<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/okh68-bde.css';
import '../../css/c/cagb5gb_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="okh68-bde"/><path class="cagb5gb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:photoshop" /></template>
