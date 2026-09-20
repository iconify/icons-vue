<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":296};
const content = `<path class="fu__b_bkz"/><path class="e0cutf27h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:neonmetrics" /></template>
<style>
.e0cutf27h {
  d: path("M98.56 219.73H60.681V87.4c0-6.122 4.963-11.086 11.086-11.086H98.56s84.175 110.632 85.008 110.102c.832-.531-26.127-39.952-26.127-39.952v-57.74c0-6.854 5.556-12.41 12.41-12.41h26.328V219.73h-34.95S77.57 110.024 76.522 110.92c-1.048.896 22.037 33.132 22.037 33.132v75.678z");
  fill: var(--svg-color--fff, #FFF);
}

.fu__b_bkz {
  d: path("M128 .397L0 74.297v50.568h7.576V78.67L128 9.144L248.424 78.67v46.194H256V74.298L128 .397zm120.424 171.298v46.03L128 287.254L7.575 217.726v-46.031H0v50.404l128 73.9l128-73.9v-50.404h-7.576zM15.33 83.147l112.67-65.05l112.673 65.05V213.25L128 278.3L15.329 213.25V83.146z");
  fill: var(--svg-color--404040, #404040);
}

</style>
