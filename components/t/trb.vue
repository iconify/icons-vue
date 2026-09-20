<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gl-a_gu0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:trb" /></template>
<style>
.gl-a_gu0z {
  fill: var(--svg-color--20fe9c, #20fe9c);
  d: path("M20.978 7.732c.61 2.422-11.4 8.407-16.845 9.83c-5.444 1.422 10.528-5.592 9.904-8.013c-.623-2.423-13.353-.437-7.91-1.86c5.445-1.422 14.24-2.38 14.85.043");
}

</style>
