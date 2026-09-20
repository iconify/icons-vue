<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="jrxqktv8b"/><path class="hqv6jmttg"/><path class="sc8ohbznu"/><path class="g0c15pbol"/><path class="v7z0ivgcs"/><path class="z1ya8bb9l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:utya" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.g0c15pbol {
  fill: var(--svg-color--fd4b03, #fd4b03);
  d: path("M12.306 10.182c.6.05 1.202.4 1.553.952c.85 0 1.652.15 2.053.75c.15.602-.3 1.203-1.202 1.604c-.801.4-1.803.55-2.354.5c-.751 0-1.853-.2-2.554-.6c-.651-.401-.902-1.002-.651-1.553c.35-.501 1.152-.701 1.903-.701c.35-.551.751-.902 1.252-.952");
}

.hqv6jmttg {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M5.995 11.885c.501.801 1.102 2.003 1.803 3.105c.802 1.202.2 3.005-1.202 2.604c-.8-.2-1.602-.901-2.203-1.803c-.802-1.202-1.352-2.404-1.102-3.305c.3-1.002 1.703-1.102 2.704-.601");
}

.jrxqktv8b {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M6.296 17.294c0-2.705 2.704-4.007 6.31-4.007c4.608 0 8.164 1.703 8.164 3.706c0 2.304-3.356 4.007-8.063 4.007c-4.107 0-6.411-1.402-6.411-3.706");
}

.sc8ohbznu {
  fill: var(--svg-color--ffd300, #ffd300);
  d: path("M12.446 3a7.102 7.102 0 1 1 0 14.204a7.102 7.102 0 1 1 0-14.204");
}

.v7z0ivgcs {
  fill: var(--svg-color--c41800, #c41800);
  d: path("M9.501 12.636c1.703.701 4.508.651 6.01-.05c-.15.55-.6.751-.801.902c-.801.4-1.803.55-2.354.5c-.751 0-1.853-.2-2.554-.6c-.3-.201-.4-.502-.3-.752");
}

.z1ya8bb9l {
  fill: var(--svg-color--000, #000);
  d: path("M9.601 8.68a.851 1.052 0 1 1 0 2.103a.851 1.052 0 1 1 0-2.103m5.309-.251a.851 1.052 0 1 1 0 2.104a.851 1.052 0 1 1 0-2.104");
}

</style>
